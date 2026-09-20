<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg2-apbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg2-apbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-percentage" /></template>
