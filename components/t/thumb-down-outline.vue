<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nml4dbbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nml4dbbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:thumb-down-outline" /></template>
