<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr59wcg0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="pr59wcg0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:poo-storm" /></template>
