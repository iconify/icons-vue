<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rosx4zbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rosx4zbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:plus-circle" /></template>
