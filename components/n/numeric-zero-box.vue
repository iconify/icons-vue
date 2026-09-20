<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgmu23bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgmu23bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-zero-box" /></template>
