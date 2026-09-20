<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfygh5brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfygh5brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vim" /></template>
