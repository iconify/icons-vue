<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaz4tobep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vaz4tobep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:manager-self-service" /></template>
