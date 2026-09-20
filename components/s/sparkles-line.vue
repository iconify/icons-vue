<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frfjtnbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frfjtnbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sparkles-line" /></template>
