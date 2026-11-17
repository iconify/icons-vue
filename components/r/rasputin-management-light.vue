<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyg63gb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pyg63gb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rasputin-management-light" /></template>
