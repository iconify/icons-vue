<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyzcv3rvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyzcv3rvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pause-circle-line" /></template>
