<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuxlfd-qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuxlfd-qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:map-pin-plus" /></template>
