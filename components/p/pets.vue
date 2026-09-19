<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9ng8-b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u9ng8-b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:pets" /></template>
