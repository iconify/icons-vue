<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njsk45-mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njsk45-mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pyramid" /></template>
