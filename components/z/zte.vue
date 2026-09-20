<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubfgqsalz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":193.3};
const content = `<path class="ubfgqsalz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zte" /></template>
