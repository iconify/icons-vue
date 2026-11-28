<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuchlbb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuchlbb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wifi-x" /></template>
