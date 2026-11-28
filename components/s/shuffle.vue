<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jso2fwbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jso2fwbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:shuffle" /></template>
