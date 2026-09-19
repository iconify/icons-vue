<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ght7cujyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ght7cujyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-glass-door2-close" /></template>
