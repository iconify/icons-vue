<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkh622bdk.css';
import '../../css/d/dr_tp8gfx.css';
import '../../css/o/otxt9vb3m.css';
import '../../css/r/rlcpunbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nkh622bdk"/><path class="dr_tp8gfx"/><path class="otxt9vb3m"/><path class="rlcpunbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:screamfear" /></template>
