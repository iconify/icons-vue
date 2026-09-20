<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfj4sf55g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfj4sf55g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-9-small" /></template>
