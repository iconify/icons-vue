<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mc0z6hiyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-line-horizontal-3-16-regular" /></template>
<style>
.mc0z6hiyq {
  fill: currentColor;
  d: path("M8.808 2.101a.9.9 0 0 0-1.614 0L5.673 5.183l-3.401.495a.9.9 0 0 0-.5 1.535l2.462 2.399l-.581 3.387a.9.9 0 0 0 1.306.949L8 12.348l.482.254a1.5 1.5 0 0 1-.474-1.266a.9.9 0 0 0-.427.103l-2.91 1.53l.556-3.24a.9.9 0 0 0-.258-.797L2.616 6.638l3.253-.473a.9.9 0 0 0 .677-.492l1.455-2.947l.733 1.484C8.958 4.076 9.22 4 9.5 4h.245zM9.5 5a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zm0 3a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zm0 3a.5.5 0 0 0 0 1h5a.5.5 0 1 0 0-1z");
}

</style>
