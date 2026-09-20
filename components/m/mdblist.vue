<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2vfkbccu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2vfkbccu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mdblist" /></template>
