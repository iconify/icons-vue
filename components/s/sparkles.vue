<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk4tjmvcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk4tjmvcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sparkles" /></template>
