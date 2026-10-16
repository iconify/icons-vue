<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymduf8c4o.css';
import '../../css/s/s0d42ac3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ymduf8c4o"/><path class="s0d42ac3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signpost-48" /></template>
