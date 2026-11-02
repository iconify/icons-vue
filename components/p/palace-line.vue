<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3xn-bbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3xn-bbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:palace-line" /></template>
