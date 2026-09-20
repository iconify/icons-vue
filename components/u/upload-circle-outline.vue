<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi6tq537p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi6tq537p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:upload-circle-outline" /></template>
