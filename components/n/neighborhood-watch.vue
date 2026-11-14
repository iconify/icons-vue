<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st1dhgb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:neighborhood-watch" /></template>
<style>
.st1dhgb5r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.701 8.886l7.75-6.119q1.549-1.222 3.098 0l7.75 6.119q.95.75.951 1.962v8.902q0 1.036-.732 1.768t-1.768.732H4.25q-1.036 0-1.768-.732T1.75 19.75v-8.902q.001-1.211.951-1.962M12 10.75q-3.825 0-6.143 3.864q-.053.088-.08.186t-.027.2t.027.2t.08.186Q8.175 19.25 12 19.25t6.143-3.864q.053-.088.08-.186t.027-.2t-.027-.2t-.08-.186Q15.825 10.75 12 10.75");
}

</style>
