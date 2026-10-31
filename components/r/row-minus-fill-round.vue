<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4-pn4mrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4-pn4mrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:row-minus-fill-round" /></template>
