<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uce955b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uce955b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:svg" /></template>
