<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaknp1bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qaknp1bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-none-20-bold" /></template>
