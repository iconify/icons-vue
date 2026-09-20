<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c29q9gyiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c29q9gyiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:mouse" /></template>
