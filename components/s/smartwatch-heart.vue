<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyqqidb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyqqidb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smartwatch-heart" /></template>
