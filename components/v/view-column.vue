<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3h4vqfxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3h4vqfxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:view-column" /></template>
