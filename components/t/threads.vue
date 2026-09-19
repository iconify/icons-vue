<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phl4jebma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phl4jebma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:threads" /></template>
