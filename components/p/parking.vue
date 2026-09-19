<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tae50hpaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":280,"height":384};
const content = `<path class="tae50hpaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:parking" /></template>
