<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8-4x2b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8-4x2b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sofa-round" /></template>
