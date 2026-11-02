<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvx5ekp3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvx5ekp3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rows-4-line" /></template>
