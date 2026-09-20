<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cry053b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cry053b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:piggy-bank" /></template>
