<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9idfkzew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9idfkzew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:martini-solid" /></template>
