<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy35efbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy35efbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:octagon-check-line" /></template>
