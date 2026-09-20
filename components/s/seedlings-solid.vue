<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtb9wxb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtb9wxb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:seedlings-solid" /></template>
