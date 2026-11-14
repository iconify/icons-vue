<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aygvukb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:playhouse" /></template>
<style>
.aygvukb-h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.104 9.412q-.854.746-.854 1.881v7.456q0 2.5 2.5 2.5H15q-1-.946-1-2.483v-1.534q0-2.071 1.815-3.068q1.816-.997 3.563.114l.001.001l1.206.768q.085.054.165.11v-3.864q0-1.135-.854-1.881L18.75 8.41V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 3.25h-2q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T15.25 4v1.347l-1.604-1.404Q12 2.504 10.354 3.944zM17.25 4.75v2.347l-.5-.437V4.75zm1.458 10.584l1.206.768q1.041.664 1.041 1.898t-1.041 1.897l-1.206.769q-1.124.714-2.291.073t-1.167-1.972v-1.534q0-1.331 1.167-1.972t2.29.073zm-.806 1.266q-.374-.238-.763-.025q-.389.214-.389.658v1.534q0 .444.389.658q.389.213.763-.025l1.206-.767q.347-.222.347-.633t-.347-.632z");
}

</style>
