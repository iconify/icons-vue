<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi_m99bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zi_m99bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:star-off-fill" /></template>
