<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz21dlb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rz21dlb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:or" /></template>
