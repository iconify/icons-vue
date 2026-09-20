<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on6e2sbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="on6e2sbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:stroller" /></template>
