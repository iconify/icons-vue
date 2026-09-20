<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uipgvcbdd.css';
import '../../css/c/cpiyk6e9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":259};
const content = `<path class="uipgvcbdd"/><path class="cpiyk6e9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pandacss" /></template>
