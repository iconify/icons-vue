<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msp13vg8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msp13vg8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-brush-broken" /></template>
