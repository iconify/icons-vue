<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr1motb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr1motb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:vinyl-star" /></template>
