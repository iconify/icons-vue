<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbi1n57ce.css';
import '../../css/m/mc8nkccec.css';
import '../../css/m/m286a39yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bbi1n57ce"/><path class="mc8nkccec"/><path class="m286a39yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:volume-mute-outline" /></template>
