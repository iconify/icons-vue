<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuzg7bx1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuzg7bx1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:property-add" /></template>
