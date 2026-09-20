<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huryb7cmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huryb7cmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:window-maximize" /></template>
