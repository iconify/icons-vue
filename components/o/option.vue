<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhvw9chnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhvw9chnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:option" /></template>
