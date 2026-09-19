<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpj_gzx8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="gpj_gzx8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:picture-in-picture" /></template>
