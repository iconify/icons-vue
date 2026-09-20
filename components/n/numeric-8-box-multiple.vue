<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9h5ad7cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9h5ad7cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-8-box-multiple" /></template>
