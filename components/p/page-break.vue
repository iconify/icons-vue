<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzqmrjbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzqmrjbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:page-break" /></template>
