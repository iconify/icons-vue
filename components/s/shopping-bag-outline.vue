<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk4yqnh0p.css';
import '../../css/m/m9tv2wbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk4yqnh0p"/><path class="m9tv2wbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:shopping-bag-outline" /></template>
