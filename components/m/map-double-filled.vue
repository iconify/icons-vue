<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe-bdwhdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe-bdwhdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-double-filled" /></template>
