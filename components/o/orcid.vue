<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svjn8gd9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svjn8gd9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:orcid" /></template>
