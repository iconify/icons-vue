<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9ncnbt5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ncnbt5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:speach-to-text" /></template>
