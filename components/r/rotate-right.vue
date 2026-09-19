<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5wag-rzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x5wag-rzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:rotate-right" /></template>
