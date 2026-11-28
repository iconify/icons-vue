<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzz1z6ryv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzz1z6ryv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:parking" /></template>
