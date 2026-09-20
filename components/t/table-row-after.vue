<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9mgdhkad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="g9mgdhkad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:table-row-after" /></template>
