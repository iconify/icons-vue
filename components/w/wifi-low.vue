<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr2jqqvqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr2jqqvqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wifi-low" /></template>
