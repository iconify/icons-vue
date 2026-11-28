<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gijp15pol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gijp15pol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:podcast-pause" /></template>
