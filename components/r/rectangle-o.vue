<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4az-pqpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="d4az-pqpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:rectangle-o" /></template>
