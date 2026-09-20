<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeug8pb_s.css';
import '../../css/k/kifmwrb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yeug8pb_s"/><path class="kifmwrb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:youtube-shorts" /></template>
