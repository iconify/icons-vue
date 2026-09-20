<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qvr1ifb2v"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qute" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.qvr1ifb2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.806 15.004v3.235a1.961 1.961 0 0 0 3.922 0v-3.236m-9.834 4.759c.358.3.745.439 1.613.439h.44c.716 0 1.296-.582 1.296-1.3c0-.717-.58-1.299-1.296-1.299h-.88a1.3 1.3 0 0 1-1.297-1.3c0-.717.58-1.298 1.297-1.298h.44c.868 0 1.255.138 1.613.438m8.828 6.84h4.902M8.5 19.872l4.903-2.599L8.5 14.675M35.578 30.09a1.961 1.961 0 1 1 3.922 0v1.274a1.961 1.961 0 1 1-3.922 0zm-2.701 0a1.961 1.961 0 1 0-3.922 0v1.274a1.961 1.961 0 0 0 3.922 0m0 1.961v-7.844m-10.245 2.647v3.236a1.961 1.961 0 0 0 3.922 0v-3.236m-10.041 4.759c.358.3.745.438 1.613.438h.44c.716 0 1.296-.582 1.296-1.299c0-.718-.58-1.3-1.296-1.3h-.88a1.3 1.3 0 0 1-1.296-1.298c0-.718.58-1.3 1.296-1.3h.44c.868 0 1.255.138 1.613.439");
}

</style>
