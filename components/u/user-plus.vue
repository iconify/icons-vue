<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0lhoibac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d0lhoibac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:user-plus" /></template>
