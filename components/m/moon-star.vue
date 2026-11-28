<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uec7-abdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uec7-abdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:moon-star" /></template>
