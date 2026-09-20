<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcctsk5am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcctsk5am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:windows10" /></template>
