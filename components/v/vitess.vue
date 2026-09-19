<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1etf0byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v1etf0byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vitess" /></template>
