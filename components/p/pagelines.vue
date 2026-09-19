<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w451sabls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1792};
const content = `<path class="w451sabls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pagelines" /></template>
