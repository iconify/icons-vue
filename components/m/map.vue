<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py-lk14be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py-lk14be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map" /></template>
