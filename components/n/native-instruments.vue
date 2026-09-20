<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plqmpyb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":76.1,"height":45};
const content = `<path class="plqmpyb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:native-instruments" /></template>
