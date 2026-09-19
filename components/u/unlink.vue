<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy71xu2ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy71xu2ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:unlink" /></template>
