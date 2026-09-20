<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnryg6bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnryg6bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openmined" /></template>
