<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4gphabrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v4gphabrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ocean-acidification-20" /></template>
