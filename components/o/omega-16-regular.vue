<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zcjmjlblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:omega-16-regular" /></template>
<style>
.zcjmjlblv {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 7 7c0 1.753-.862 3.222-1.773 4.287A11.5 11.5 0 0 1 11.384 14H14.5a.5.5 0 0 1 0 1h-3.682a.82.82 0 0 1-.814-.734L10 14.182l.007-.106a.83.83 0 0 1 .366-.587c.767-.537 1.483-1.137 2.094-1.851C13.3 10.664 14 9.419 14 8A6 6 0 0 0 2 8c0 1.42.7 2.664 1.533 3.638c.83.97 1.75 1.624 2.094 1.851a.83.83 0 0 1 .373.693a.82.82 0 0 1-.818.818H1.5a.5.5 0 0 1 0-1h3.117a11.5 11.5 0 0 1-1.845-1.713C1.862 11.222 1 9.753 1 8a7 7 0 0 1 7-7");
}

</style>
