<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxuzz-civ.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxuzz-civ"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:plus" /></template>
