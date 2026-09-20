<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge5bx9bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge5bx9bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:thumb-up" /></template>
