<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7skdvj0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="c7skdvj0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:subscript" /></template>
