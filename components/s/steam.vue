<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-v5rpg1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="h-v5rpg1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:steam" /></template>
