<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erzf03bmv.css';
import '../../css/r/rplob1ewi.css';
import '../../css/a/a0910tb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="erzf03bmv"/><path class="rplob1ewi"/><path class="a0910tb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:yt-1x1" /></template>
