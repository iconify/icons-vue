<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vao4db3gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vao4db3gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:palette-filled" /></template>
