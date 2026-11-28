<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybl66cczw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybl66cczw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-diamond-solid" /></template>
