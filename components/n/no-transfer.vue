<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5toj2bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-transfer" /></template>
<style>
.o5toj2bhz {
  fill: currentColor;
  d: path("m21.11 22.53l-5.04-5.04h1.426v2.01q0 .213-.143.356t-.357.144h-.265q-.213 0-.357-.144t-.143-.356V18H7.769v1.5q0 .213-.144.356T7.27 20h-.23q-.213 0-.357-.144T6.54 19.5v-1.896q-.489-.212-1.014-.901T5 15.115V6.421L1.887 3.308l.713-.714l19.223 19.223zm-2.27-6.507L13.817 11H18V6.539H9.356l-2.77-2.77q.862-.384 2.199-.577T12 3q3.763 0 5.381.694T19 6v9.116q0 .231-.046.455q-.046.223-.114.452m-9.547-.734q.322-.327.322-.793q0-.467-.326-.79q-.327-.321-.794-.321q-.466 0-.788.326q-.323.327-.323.793q0 .467.327.79q.327.322.793.322q.467 0 .79-.327M6 11h3.579L6 7.421z");
}

</style>
