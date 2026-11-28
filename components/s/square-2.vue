<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj3h-ftar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj3h-ftar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:square-2" /></template>
