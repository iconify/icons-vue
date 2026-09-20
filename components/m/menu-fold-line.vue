<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/difr24bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="difr24bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-fold-line" /></template>
