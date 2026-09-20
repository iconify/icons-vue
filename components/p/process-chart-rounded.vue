<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb-3-9b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:process-chart-rounded" /></template>
<style>
.pb-3-9b-b {
  fill: currentColor;
  d: path("M2.4 18q-.375-.2-.512-.587t.062-.763l5.1-10.2q.2-.375.588-.512T8.4 6t.513.588t-.063.762l-5.1 10.2q-.2.375-.587.513T2.4 18m6.088-.587q-.138-.388.062-.763l5.1-10.2q.2-.375.588-.512T15 6t.513.588t-.063.762l-5.1 10.2q-.2.375-.587.513T9 18t-.513-.587m6.6 0q-.137-.388.063-.763l5.1-10.2q.2-.375.588-.512T21.6 6t.513.588t-.063.762l-5.1 10.2q-.2.375-.587.513T15.6 18t-.512-.587");
}

</style>
