<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly5v89bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly5v89bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:parentheses-gloss" /></template>
