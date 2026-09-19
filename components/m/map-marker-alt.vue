<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7t5znbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="n7t5znbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:map-marker-alt" /></template>
