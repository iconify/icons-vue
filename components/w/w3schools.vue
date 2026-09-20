<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_-opib2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_-opib2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:w3schools" /></template>
