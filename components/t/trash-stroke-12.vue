<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e12qxeb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e12qxeb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:trash-stroke-12" /></template>
