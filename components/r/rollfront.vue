<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf1_e-bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf1_e-bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:rollfront" /></template>
