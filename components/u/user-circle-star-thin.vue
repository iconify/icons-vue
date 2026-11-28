<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/par-0gblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="par-0gblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-circle-star-thin" /></template>
