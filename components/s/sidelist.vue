<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehue37sqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ehue37sqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sidelist" /></template>
