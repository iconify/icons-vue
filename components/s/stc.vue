<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t99oo8baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":499.614};
const content = `<path class="t99oo8baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:stc" /></template>
