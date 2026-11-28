<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7l_8nbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7l_8nbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:notification" /></template>
