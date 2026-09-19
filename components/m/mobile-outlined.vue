<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej3fxxlaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ej3fxxlaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:mobile-outlined" /></template>
