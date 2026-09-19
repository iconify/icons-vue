<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c72l8qbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c72l8qbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:prestashop" /></template>
