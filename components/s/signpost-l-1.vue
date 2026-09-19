<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbh3g-16i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbh3g-16i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:signpost-l-1" /></template>
