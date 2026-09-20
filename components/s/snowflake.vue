<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-3upowbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="o-3upowbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:snowflake" /></template>
