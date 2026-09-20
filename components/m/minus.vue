<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4i2tpblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4i2tpblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:minus" /></template>
