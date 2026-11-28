<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi0upab2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi0upab2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-off-solid" /></template>
