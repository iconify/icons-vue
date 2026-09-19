<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn5mcfbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hn5mcfbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:mona" /></template>
