<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp86vqbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="rp86vqbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:venus-double" /></template>
