<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoxqbl1yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<path class="qoxqbl1yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:sunglasses-alt" /></template>
