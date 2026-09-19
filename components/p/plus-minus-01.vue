<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwa1c4o_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwa1c4o_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plus-minus-01" /></template>
