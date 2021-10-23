<template>
  <div>
    {{ episodesByIds }}
  </div>
</template>
<script>
import episodes from '~/plugins/apollo/episodes.gql';

export default {
  apollo: {
    episodesByIds: {
      query: episodes,
    },
  },
};
</script>
