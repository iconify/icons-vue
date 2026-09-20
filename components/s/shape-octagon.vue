<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvytt_1zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvytt_1zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:shape-octagon" /></template>
