<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz6yyhbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-dumpling" /></template>
<style>
.pz6yyhbgs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.733 11.343q-.778-3.633-3.102-7.248v-.001q-.079-.123-.199-.207q4.728 3.31 6.518 5.444q2.8 3.338 2.8 7.669q0 3.25-3.25 3.25h-13q-3.25 0-3.25-3.25q0-4.331 2.8-7.669q1.79-2.134 6.517-5.444l-.002.002q-.118.084-.196.205q-2.324 3.615-3.102 7.249q-.016.072-.017.146t.012.146q.014.073.041.142t.067.13t.092.115q.051.053.112.095t.129.072t.14.044q.072.016.146.017t.146-.012q.073-.014.142-.041t.13-.067t.115-.092q.053-.051.095-.112t.072-.129t.044-.14Q10.345 8.805 12 5.939q1.655 2.866 2.267 5.718q.015.072.044.14q.03.068.072.129t.095.112t.115.092q.062.04.13.067q.069.027.142.041q.072.013.146.012t.146-.017t.14-.044q.068-.03.129-.072t.112-.095t.092-.115q.04-.062.067-.13q.027-.069.041-.142q.013-.072.012-.146t-.017-.146");
}

</style>
