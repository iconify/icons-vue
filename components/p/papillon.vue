<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r_es63buz"/><path class="j40gxuxgd"/><path class="n8uu1x3me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:papillon" /></template>
<style>
.j40gxuxgd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.307 12.675c4.53 5.666 5.809 12.101 2.857 14.372h0c-2.952 2.272-9.017-.48-13.546-6.147c-4.53-5.667-5.809-12.102-2.857-14.373h0c2.952-2.271 9.017.481 13.546 6.148");
}

.n8uu1x3me {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.175 17.895c7.368 1.088 12.771 4.67 12.068 8h0c-.702 3.329-7.245 5.146-14.613 4.057s-12.771-4.67-12.068-8h0c.702-3.33 7.245-5.146 14.613-4.057");
}

.r_es63buz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.285 30.198c-2.682 7.428-6.742 12.797-9.07 11.991h0c-2.327-.805-2.04-7.479.642-14.907h0c2.682-7.428 6.742-12.796 9.07-11.991h0c2.327.805 2.04 7.479-.642 14.907");
}

</style>
