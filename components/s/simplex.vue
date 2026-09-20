<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rko2gt8go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rko2gt8go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:simplex" /></template>
