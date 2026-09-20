<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9jrrcc_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c9jrrcc_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:stylo" /></template>
