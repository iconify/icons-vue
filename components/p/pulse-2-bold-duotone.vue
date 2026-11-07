<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1ktr8brq.css';
import '../../css/m/mug5xin-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1ktr8brq"/><path class="mug5xin-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pulse-2-bold-duotone" /></template>
