<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfx76kboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfx76kboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:steps-up" /></template>
