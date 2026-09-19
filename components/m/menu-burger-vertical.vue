<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhcisp32j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhcisp32j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-burger-vertical" /></template>
