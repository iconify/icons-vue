<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwg48r4wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwg48r4wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mingw-w64" /></template>
