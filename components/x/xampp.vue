<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm8umtxld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm8umtxld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:xampp" /></template>
