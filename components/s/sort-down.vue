<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tua0aq4ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="tua0aq4ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sort-down" /></template>
