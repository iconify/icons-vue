<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9q9v98uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9q9v98uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mouse-fill" /></template>
