<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q126ik-do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="q126ik-do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:wifi3" /></template>
