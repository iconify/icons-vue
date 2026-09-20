<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/genf906_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="genf906_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:night-moon-begin" /></template>
