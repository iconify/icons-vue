<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7soc3hbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:windmill-classic" /></template>
<style>
.b7soc3hbd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.833 2.917q1.591 1.591 0 3.181l-2.121 2.121q-.22.22-.22.531t.22.531l2.121 2.121q1.591 1.591 0 3.181q-1.393 1.393-2.786.347l2.644 6.279q.059.14.059.291q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7q-.151 0-.291-.059q-.138-.058-.242-.164q-.105-.106-.162-.244q-.056-.138-.055-.287q.001-.15.059-.287l2.644-6.279q-1.393 1.046-2.786-.347q-1.591-1.591 0-3.181l2.121-2.121q.22-.22.22-.531t-.22-.531L6.167 6.098q-1.591-1.591 0-3.181t3.181 0l2.121 2.121q.22.22.531.22t.53-.22l2.122-2.121q1.59-1.591 3.181 0M11.5 20.75h1v-2q0-.5-.5-.5t-.5.5zm2.5 0h1.87l-3.553-8.44q-.145-.068-.317-.068t-.317.068L8.13 20.75H10v-2q0-2 2-2t2 2z");
}

</style>
