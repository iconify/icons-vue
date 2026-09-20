<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in8z9lbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in8z9lbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:playground-fill" /></template>
