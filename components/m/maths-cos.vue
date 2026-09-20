<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amrhr5zub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amrhr5zub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:maths-cos" /></template>
