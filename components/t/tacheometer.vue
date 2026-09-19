<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/annezhqqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="annezhqqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:tacheometer" /></template>
