<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuq0gueht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuq0gueht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-double-large-duotone-round" /></template>
