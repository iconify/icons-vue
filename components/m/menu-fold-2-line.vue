<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygh_68bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygh_68bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-fold-2-line" /></template>
