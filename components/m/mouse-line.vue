<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr2x1qb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr2x1qb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:mouse-line" /></template>
