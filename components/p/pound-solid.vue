<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h15ryn7dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="h15ryn7dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pound-solid" /></template>
