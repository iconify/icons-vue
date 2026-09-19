<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxlj_x0ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxlj_x0ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:video-slash" /></template>
