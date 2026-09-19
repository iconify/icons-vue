<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp4ozmbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wp4ozmbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:rouble" /></template>
