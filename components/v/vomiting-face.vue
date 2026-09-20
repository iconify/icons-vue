<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg62jd46k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mg62jd46k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vomiting-face" /></template>
