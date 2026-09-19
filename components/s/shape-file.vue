<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6wzr80le.css';
import '../../css/y/yt-9su_gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="f6wzr80le"/><path class="yt-9su_gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:shape-file" /></template>
