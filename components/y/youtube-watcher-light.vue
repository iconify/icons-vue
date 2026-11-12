<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5xq98bou.css';
import '../../css/r/r5_089bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5xq98bou"/><path class="r5_089bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:youtube-watcher-light" /></template>
