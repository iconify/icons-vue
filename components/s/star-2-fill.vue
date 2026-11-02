<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okjvjhxqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okjvjhxqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:star-2-fill" /></template>
