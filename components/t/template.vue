<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlsfxhb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rlsfxhb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:template" /></template>
