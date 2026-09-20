<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glpwanriu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glpwanriu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wardrobe-2-fill" /></template>
