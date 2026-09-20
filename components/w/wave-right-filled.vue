<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnk4x_bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnk4x_bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wave-right-filled" /></template>
