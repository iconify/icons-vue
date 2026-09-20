<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr1nvqpte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cr1nvqpte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:takeout" /></template>
