<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs2mikx-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="rs2mikx-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mode-dark-filled" /></template>
