<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r29iocc1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r29iocc1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sofa-heart" /></template>
