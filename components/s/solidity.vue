<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":398};
const content = `<path class="jr-cxg6uc"/><path class="qubo7zbzx"/><path class="d4_1l0p4i"/><path class="e4vnxnb9t"/><path class="qyc_vxbyv"/><path class="p2820ac4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:solidity" /></template>
<style>
.d4_1l0p4i {
  d: path("m63.823 226.981l63.823-113.469L63.823 0L0 113.512z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.e4vnxnb9t {
  d: path("m64.442 397.25l63.867-113.513H256L192.132 397.25z");
  opacity: var(--svg-opacity--0-45, 0.45);
}

.jr-cxg6uc {
  d: path("m191.513 0l-63.867 113.512H0L63.823 0z");
  opacity: var(--svg-opacity--0-45, 0.45);
}

.p2820ac4b {
  d: path("m192.132 170.269l-63.823 113.468l63.823 113.513L256 283.737z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.qubo7zbzx {
  d: path("M127.646 113.512h127.691L191.513 0H63.823z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.qyc_vxbyv {
  d: path("M128.309 283.737H.618L64.441 397.25h127.691z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

</style>
