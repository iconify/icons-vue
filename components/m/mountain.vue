<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1-q9we5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h1-q9we5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:mountain" /></template>
