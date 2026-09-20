<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s86e7cc1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s86e7cc1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mounted-slotted-dispenser-with-poo-pile" /></template>
