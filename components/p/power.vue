<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm1mhyw_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rm1mhyw_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:power" /></template>
