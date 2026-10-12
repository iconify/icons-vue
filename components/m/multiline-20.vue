<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqcuttcnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oqcuttcnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:multiline-20" /></template>
