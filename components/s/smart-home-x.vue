<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi8346r3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi8346r3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smart-home-x" /></template>
