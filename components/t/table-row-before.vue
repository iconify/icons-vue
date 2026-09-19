<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqr9zzbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hqr9zzbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:table-row-before" /></template>
