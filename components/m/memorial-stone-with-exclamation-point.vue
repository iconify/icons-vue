<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hssezr-nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hssezr-nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-exclamation-point" /></template>
