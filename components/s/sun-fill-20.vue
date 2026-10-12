<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4tokcr5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k4tokcr5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sun-fill-20" /></template>
