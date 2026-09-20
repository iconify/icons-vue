<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj4jnki3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="sj4jnki3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:table-cell" /></template>
