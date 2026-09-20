<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eez8o0bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":90,"height":22};
const content = `<path class="eez8o0bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:upsales" /></template>
