<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofmkj9b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ofmkj9b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:viaf-square" /></template>
