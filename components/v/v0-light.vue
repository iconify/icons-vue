<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0s4wmb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d0s4wmb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:v0-light" /></template>
