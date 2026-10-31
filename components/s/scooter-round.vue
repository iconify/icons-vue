<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueybqgfhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueybqgfhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scooter-round" /></template>
