<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":296};
const content = `<path class="qq9-wobbr"/><path class="eg96okjez"/><path class="ge6mlrb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:pyup" /></template>
<style>
.eg96okjez {
  fill: var(--svg-color--2e6371, #2e6371);
  d: path("m0 220.735l51.81 30.389V103.637l.005-.003L0 74.039zm91.649 53.756l36.608 21.472l.486-1.21v-59.355l-.486-1.062l-36.608-19.094zm-.384-148.324v42.882l36.976 21.067l.016-.009l.148-.338l-.011-42.233l-.137-.24z");
}

.ge6mlrb8w {
  fill: var(--svg-color--1bafce, #1bafce);
  d: path("M204.753 102.902v89.008l-76.495 42.425v61.628L256 220.734V73.161zm-39.505 22.927l-36.991 21.467v42.81l36.99-21.168z");
}

.qq9-wobbr {
  fill: var(--svg-color--4f859a, #4f859a);
  d: path("M91.265 126.16v.007l.33.304l36.633 21.266l36.782-21.64l.238-.268v-.005l-37.195-20.605zm113.488-23.258l.503-.014L255.67 73.63l.33-.469l-51.247-29.328zM128.157 0L0 74.038l.425.744l50.71 28.965l.68-.113l76.443-43.791l36.966 22.094V21.212z");
}

</style>
