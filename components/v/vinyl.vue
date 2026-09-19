<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6jhh5tia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d6jhh5tia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:vinyl" /></template>
