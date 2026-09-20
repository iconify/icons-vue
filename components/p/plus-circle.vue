<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv_7k8bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="nv_7k8bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:plus-circle" /></template>
