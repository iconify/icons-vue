<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gig3dcc4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gig3dcc4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:watch-2-line" /></template>
