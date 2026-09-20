<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khw-9n4qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="khw-9n4qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:torch" /></template>
