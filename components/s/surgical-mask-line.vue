<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn_fhibxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn_fhibxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:surgical-mask-line" /></template>
