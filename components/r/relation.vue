<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufr4y318d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufr4y318d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:relation" /></template>
