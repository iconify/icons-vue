<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp_v__9ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp_v__9ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ray" /></template>
