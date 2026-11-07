<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w06k5-7cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w06k5-7cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:toolbox-bold" /></template>
