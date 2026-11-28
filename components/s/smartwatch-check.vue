<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3s66abna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3s66abna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smartwatch-check" /></template>
