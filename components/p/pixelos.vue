<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7yr9bbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="l7yr9bbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pixelos" /></template>
