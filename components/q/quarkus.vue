<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t41a-9_dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t41a-9_dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:quarkus" /></template>
