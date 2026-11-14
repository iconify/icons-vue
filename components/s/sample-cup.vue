<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptbjb82oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sample-cup" /></template>
<style>
.ptbjb82oo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.25 3.75H5.75q-2.5 0-2.5 2.5q0 1.61 1.036 2.183l.964 10.603q.018 2.214 2.25 2.214h9q2.232 0 2.25-2.214l.964-10.603Q20.75 7.86 20.75 6.25q0-2.5-2.5-2.5m-8.25 7h4q.932 0 1.591.659T16.25 13v2q0 .932-.659 1.591T14 17.25h-4q-2.25 0-2.25-2.25v-2q0-2.25 2.25-2.25");
}

</style>
