<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orobg4brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orobg4brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:squircle" /></template>
