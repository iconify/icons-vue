<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lek2xnz1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lek2xnz1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toggle-left-line" /></template>
