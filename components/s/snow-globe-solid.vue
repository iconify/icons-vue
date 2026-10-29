<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptkb62c8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptkb62c8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:snow-globe-solid" /></template>
