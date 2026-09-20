<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw3xdtbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw3xdtbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:myanimelist" /></template>
