<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg_f1--9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg_f1--9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:stop-sign" /></template>
