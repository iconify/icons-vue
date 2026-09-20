<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju8rpyy-e.css';
import '../../css/e/e7xj5wb7j.css';
import '../../css/v/vqybd9jdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju8rpyy-e"/><path class="e7xj5wb7j"/><path class="vqybd9jdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:video-meeting-team-monitor-man" /></template>
