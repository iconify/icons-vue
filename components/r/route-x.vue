<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpxy3besi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpxy3besi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:route-x" /></template>
