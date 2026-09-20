<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fofr1v_oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fofr1v_oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:play" /></template>
