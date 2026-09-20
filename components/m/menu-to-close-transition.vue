<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xro_uz.css';
import '../../css/d/d-xntmfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xro_uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:menu-to-close-transition" /></template>
