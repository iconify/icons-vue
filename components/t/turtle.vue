<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmc4ovo2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qmc4ovo2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:turtle" /></template>
