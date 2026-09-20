<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5fl45vmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h5fl45vmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:poo-pile" /></template>
