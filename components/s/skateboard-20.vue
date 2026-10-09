<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-bjsbcho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x-bjsbcho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skateboard-20" /></template>
