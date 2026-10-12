<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hawd1sbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hawd1sbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plug-stroke-20" /></template>
