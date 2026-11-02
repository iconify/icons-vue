<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3a0q5wsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3a0q5wsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shield-fill" /></template>
