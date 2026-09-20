<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnt8-f7wi.css';
import '../../css/g/gnytiu9gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bnt8-f7wi"/><path class="gnytiu9gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:social-rewards-trends-hot-flame" /></template>
