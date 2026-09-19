<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vabbgtf6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="vabbgtf6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mattress-pillow" /></template>
