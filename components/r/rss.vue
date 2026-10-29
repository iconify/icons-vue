<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew13tbxvb.css';
import '../../css/a/al19bfb5b.css';
import '../../css/j/jmiuoqhtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew13tbxvb wm-k"/><path class="al19bfb5b wm-a"/><path class="jmiuoqhtu wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:rss" /></template>
