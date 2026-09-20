<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltwtj0gsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ltwtj0gsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sort-numeric-down-solid" /></template>
