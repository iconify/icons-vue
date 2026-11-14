<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so421j83k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:process-kill" /></template>
<style>
.so421j83k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.722 15.767l-4.746 2.848q-.149.089-.308.158t-.326.117t-.338.072t-.346.027q-.173.002-.345-.018q-.172-.021-.341-.064q-.168-.043-.328-.108q-.161-.065-.312-.15q-.151-.086-.29-.19t-.261-.227q-.124-.122-.23-.259t-.194-.287t-.154-.31t-.112-.327t-.068-.34T4 16.364V7.636q0-.173.023-.345t.068-.34q.045-.167.112-.327t.154-.31q.088-.15.194-.287t.23-.259t.261-.227q.139-.104.29-.19q.151-.085.312-.15q.16-.065.328-.108q.169-.043.341-.064q.172-.02.345-.018q.174.002.346.027t.338.072q.167.048.326.117t.308.158l7.272 4.364q.095.057.185.122q.089.064.173.136t.162.151t.148.164q.071.085.135.176q.063.091.118.187q.056.095.103.196q.047.1.086.203t.068.211q.03.106.05.215t.033.219q.011.11.013.221q.002.11-.005.221q-.007.11-.024.22q-.016.109-.042.217q-.025.107-.06.212M15.5 15.5l5 5m0-5l-5 5");
}

</style>
