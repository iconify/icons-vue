<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjsyi-n3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gjsyi-n3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:sib" /></template>
