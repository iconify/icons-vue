<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knsfxbc3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knsfxbc3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:w3schools" /></template>
