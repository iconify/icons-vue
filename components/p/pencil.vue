<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsvs-7g4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qsvs-7g4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:pencil" /></template>
