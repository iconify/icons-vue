<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo64yvbkk.css';
import '../../css/q/q5h959_9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xo64yvbkk"/><path class="q5h959_9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pen-sparkle-48" /></template>
