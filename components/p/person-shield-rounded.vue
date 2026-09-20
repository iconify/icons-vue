<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8_dnxt7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-shield-rounded" /></template>
<style>
.g8_dnxt7y {
  fill: currentColor;
  d: path("M17.422 20.897q-.133-.028-.264-.078q-1.281-.528-2.027-1.738t-.747-2.665v-1.637q0-.217.11-.41t.325-.298l2.5-1.269q.181-.086.373-.086t.374.086l2.5 1.27q.217.105.325.297q.109.193.109.41v1.637q0 1.455-.746 2.665t-2.027 1.738q-.13.05-.264.078t-.27.028t-.271-.028M6.038 18.616q-.44 0-.739-.3Q5 18.017 5 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.155-.548 2.374-.894t2.498-.433q.321-.03.56.208q.238.238.238.56v2.002q0 .338.027.683t.1.678q.067.327-.121.583q-.189.256-.51.256zm3.839-8.108Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877");
}

</style>
