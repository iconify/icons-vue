<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab6fy1brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ab6fy1brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:steam" /></template>
