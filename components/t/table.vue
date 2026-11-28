<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhqb9sbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhqb9sbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:table" /></template>
