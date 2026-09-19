<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unur3-b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unur3-b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:minus-square-fill" /></template>
