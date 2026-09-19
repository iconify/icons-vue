<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbg_emk3p.css';
import '../../css/q/qrb1vdrhq.css';
import '../../css/w/whu0plbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tbg_emk3p"/><path class="qrb1vdrhq"/><path class="whu0plbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pagefacingup" /></template>
