<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8q4kke-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8q4kke-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:strike-through" /></template>
