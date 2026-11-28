<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm-1nv75i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm-1nv75i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:virus-check" /></template>
