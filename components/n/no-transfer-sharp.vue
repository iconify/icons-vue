<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efsa3ub7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-transfer-sharp" /></template>
<style>
.efsa3ub7u {
  fill: currentColor;
  d: path("m21.11 22.53l-5.04-5.04h1.426V20h-1.265v-2H7.769v2H6.54v-2.396q-.489-.212-1.014-.901T5 15.115V6.421L1.887 3.308l.713-.714l19.223 19.223zm-2.27-6.507L13.817 11H18V6.539H9.356l-2.77-2.77q.862-.384 2.199-.577T12 3q3.763 0 5.381.694T19 6v9.116q0 .231-.046.455q-.046.223-.114.452m-9.547-.734q.322-.327.322-.793q0-.467-.326-.79q-.327-.321-.794-.321q-.466 0-.788.326q-.323.327-.323.793q0 .467.327.79q.327.322.793.322q.467 0 .79-.327M6 11h3.579L6 7.421z");
}

</style>
