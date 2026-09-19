<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4c47gkwc.css';
import '../../css/r/rvgwmpbdo.css';
import '../../css/x/xp27v-b4z.css';
import '../../css/r/r7-o3sbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r4c47gkwc"/><path class="rvgwmpbdo"/><path class="xp27v-b4z"/><path class="r7-o3sbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:onebuttonmouse" /></template>
