<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8hjs2bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h8hjs2bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:sum" /></template>
