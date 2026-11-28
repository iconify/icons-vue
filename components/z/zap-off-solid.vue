<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz5-4qtmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz5-4qtmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zap-off-solid" /></template>
