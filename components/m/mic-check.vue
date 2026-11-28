<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-lswx_ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-lswx_ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mic-check" /></template>
