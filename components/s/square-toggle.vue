<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg1oycbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg1oycbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-toggle" /></template>
