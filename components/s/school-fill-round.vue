<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecj1oabrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecj1oabrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:school-fill-round" /></template>
