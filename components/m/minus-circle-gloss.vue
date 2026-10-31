<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg6h2wgtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg6h2wgtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:minus-circle-gloss" /></template>
