<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-pvd6swv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-pvd6swv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:uplighter" /></template>
