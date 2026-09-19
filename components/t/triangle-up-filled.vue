<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd7gesedg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yd7gesedg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:triangle-up-filled" /></template>
