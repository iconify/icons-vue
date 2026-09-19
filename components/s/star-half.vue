<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0z39514c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b0z39514c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:star-half" /></template>
