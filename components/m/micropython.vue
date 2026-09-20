<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/der6foqae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="der6foqae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:micropython" /></template>
