<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de84vab6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":34,"height":32};
const content = `<path class="de84vab6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:trophy" /></template>
