<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-vkvrb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-vkvrb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openstreetmap" /></template>
