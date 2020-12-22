<template>
  <div>
    <UnderConstruction msg="Website under construction" />
    <router-view />
  </div>
</template>

<script>
import UnderConstruction from '@/components/UnderConstruction.vue';

export default {
  name: 'Home',
  components: {
    UnderConstruction
  }
};
</script>
