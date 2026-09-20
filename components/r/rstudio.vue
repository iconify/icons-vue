<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn2h7mb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn2h7mb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rstudio" /></template>
