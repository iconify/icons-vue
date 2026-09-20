<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aguem8bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="aguem8bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:udacity" /></template>
