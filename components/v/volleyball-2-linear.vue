<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi41mr-8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi41mr-8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volleyball-2-linear" /></template>
