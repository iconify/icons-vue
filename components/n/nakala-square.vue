<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc8j7xilh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xc8j7xilh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:nakala-square" /></template>
