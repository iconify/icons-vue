<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thk5s-brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="thk5s-brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:spacex" /></template>
