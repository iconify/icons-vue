<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fml_aabun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-2-outline-rounded" /></template>
<style>
.fml_aabun {
  fill: currentColor;
  d: path("M13.208 15.175q.476-.477.436-1.147t-.586-1.06q-1.327-.964-2.666-1.907T7.715 9.183q-.298-.21-.54.031t-.03.54q.947 1.342 1.893 2.672t1.912 2.65q.404.552 1.083.574t1.175-.474M5.106 19q-.278 0-.511-.112q-.233-.113-.393-.338q-.604-1.076-.906-2.252q-.302-1.177-.302-2.41q0-.868.166-1.712q.165-.843.515-1.643q.074-.175.272-.24q.197-.064.374.02q.177.085.247.29t-.002.393q-.302.696-.437 1.422q-.135.727-.135 1.482q0 1.1.268 2.138T5.108 18H18.9q.525-.9.813-1.912T20 14q0-3.325-2.337-5.663T12 6q-.655 0-1.286.11q-.63.11-1.237.307q-.208.068-.4-.012T8.8 6.133t-.003-.387t.286-.269q.729-.229 1.45-.353Q11.253 5 11.962 5q1.863 0 3.512.701t2.877 1.92t1.939 2.867q.71 1.649.71 3.503q0 1.207-.302 2.346t-.894 2.136q-.142.264-.387.395T18.9 19zm7.023-4.854");
}

</style>
