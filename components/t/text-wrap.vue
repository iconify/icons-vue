<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzyvuacov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzyvuacov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:text-wrap" /></template>
