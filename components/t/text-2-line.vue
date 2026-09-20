<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du1gcbhpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du1gcbhpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-2-line" /></template>
