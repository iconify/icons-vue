<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqox9xelv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqox9xelv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-x" /></template>
