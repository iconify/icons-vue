<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9nen1bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9nen1bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-add-plus" /></template>
