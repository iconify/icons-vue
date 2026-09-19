<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2uf_k-ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="r2uf_k-ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-walking-luggage" /></template>
