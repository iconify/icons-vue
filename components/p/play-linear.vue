<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw9fsrbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw9fsrbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:play-linear" /></template>
