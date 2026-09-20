<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw2c6mblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gw2c6mblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tshirt-on-clothes-hanger-and-folded-linens" /></template>
