<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgdi6d99q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgdi6d99q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:right-to-left-text-direction" /></template>
