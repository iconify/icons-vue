<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lenrsb8cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lenrsb8cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:scroll-bar-filled" /></template>
