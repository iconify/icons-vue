<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnr7_ug-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hnr7_ug-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:v0-dark" /></template>
