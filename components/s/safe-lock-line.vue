<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr7o1ig4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr7o1ig4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-lock-line" /></template>
