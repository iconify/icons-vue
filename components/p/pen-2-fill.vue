<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac-5x1biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac-5x1biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pen-2-fill" /></template>
