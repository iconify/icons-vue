<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7zsl-bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7zsl-bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:todo-fill" /></template>
