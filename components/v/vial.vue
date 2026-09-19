<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_ntt-odb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ntt-odb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:vial" /></template>
