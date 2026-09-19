<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt0e9ox5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1408};
const content = `<path class="gt0e9ox5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:square-o" /></template>
