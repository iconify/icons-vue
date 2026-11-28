<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovc778baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovc778baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:square-3" /></template>
