<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cokt-3b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cokt-3b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qq" /></template>
