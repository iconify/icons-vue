<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oerhiyb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oerhiyb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mask" /></template>
