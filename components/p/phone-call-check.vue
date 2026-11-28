<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j23y-g-2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j23y-g-2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:phone-call-check" /></template>
