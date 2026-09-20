<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="exa384bab"/><path class="tst0owg3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:name-badge" /></template>
<style>
.exa384bab {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M28.303 2.576c-.449-.317-1.017-.173-1.263.319l-2.595 5.21c-.245.492-.695.521-1.001.064L18.556.86c-.306-.457-.806-.457-1.112 0l-4.888 7.308c-.306.457-.757.428-1.002-.064L8.96 2.895a.834.834 0 0 0-1.263-.319S0 8 0 20c0 7.732 8.059 16 18 16s18-8.268 18-16c0-12-7.697-17.424-7.697-17.424");
}

.tst0owg3i {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M32 23a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2z");
}

</style>
