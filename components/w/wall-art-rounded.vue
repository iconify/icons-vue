<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc9fzacky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wall-art-rounded" /></template>
<style>
.bc9fzacky {
  fill: currentColor;
  d: path("M4.616 21q-.691 0-1.153-.462T3 19.385V8.615q0-.69.463-1.152T4.615 7h4.27l2.55-2.55q.242-.242.565-.242t.566.242L15.116 7h4.269q.69 0 1.153.463T21 8.616v10.769q0 .69-.462 1.153T19.385 21zm6.596-3.962l-1.427-1.725q-.131-.142-.314-.142q-.182 0-.313.162l-1.154 1.52q-.162.212-.05.43q.112.217.354.217h7.538q.243 0 .354-.217t-.03-.43l-2.02-2.713q-.13-.161-.323-.161q-.192 0-.323.162zm6.504-4.36q.323-.322.323-.794q0-.47-.323-.793q-.322-.322-.793-.322t-.793.322t-.322.793t.322.794t.793.322t.793-.322M10.138 7h3.724L12 5.139z");
}

</style>
