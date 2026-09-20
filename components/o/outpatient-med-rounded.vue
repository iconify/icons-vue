<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd-gibf9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:outpatient-med-rounded" /></template>
<style>
.xd-gibf9g {
  fill: currentColor;
  d: path("M3.366 5.23q-.214 0-.357-.142t-.143-.357t.143-.357t.357-.143h9q.213 0 .356.143q.144.143.144.357t-.144.357t-.356.143zm5.293 11.563q.322-.322.322-.793v-1.384h1.385q.47 0 .793-.323q.322-.322.322-.793t-.322-.793q-.322-.323-.793-.323H8.98V11q0-.471-.322-.793t-.793-.323t-.794.323T6.75 11v1.385H5.366q-.472 0-.794.322t-.322.793t.322.793t.794.323H6.75V16q0 .471.322.793t.794.323q.47 0 .793-.323M3.48 20q-.69 0-1.153-.462t-.462-1.153v-9.77q0-.69.462-1.152T3.481 7h8.769q.69 0 1.153.463t.463 1.153v9.769q0 .69-.463 1.153T12.25 20zm15.486-5.546q-.165-.166-.165-.367t.165-.366l1.26-1.221h-3.38q-.195 0-.338-.153T16.366 12t.147-.337t.333-.144h3.381l-1.221-1.221q-.165-.165-.175-.354t.157-.354t.37-.165t.37.166l1.859 1.851q.244.24.244.56t-.242.564L19.7 14.454q-.165.165-.366.165t-.367-.165");
}

</style>
