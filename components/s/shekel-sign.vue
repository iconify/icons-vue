<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyuwbmihz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jyuwbmihz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:shekel-sign" /></template>
