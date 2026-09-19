<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca0nzq7-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ca0nzq7-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:type-fill" /></template>
