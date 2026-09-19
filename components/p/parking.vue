<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opip_vb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="opip_vb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:parking" /></template>
