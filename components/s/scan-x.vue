<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo3lo3bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo3lo3bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:scan-x" /></template>
