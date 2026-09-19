<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_e83v4za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1408};
const content = `<path class="o_e83v4za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:p" /></template>
