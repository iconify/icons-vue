<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdd20qqvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdd20qqvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-ruler-filled" /></template>
