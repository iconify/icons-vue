<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5c_j2bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1408};
const content = `<path class="c5c_j2bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:minus-square-o" /></template>
