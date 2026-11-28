<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egv3yy4my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egv3yy4my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:volleyball" /></template>
