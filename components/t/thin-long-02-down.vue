<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz-o-n5vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz-o-n5vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:thin-long-02-down" /></template>
