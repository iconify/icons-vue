<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grn-okb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grn-okb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vectary" /></template>
