<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc5o9yeae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":250,"height":62.734};
const content = `<path class="vc5o9yeae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:uchicago" /></template>
