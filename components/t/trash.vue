<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exq42-b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="exq42-b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:trash" /></template>
