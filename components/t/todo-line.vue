<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzr7vhb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzr7vhb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:todo-line" /></template>
