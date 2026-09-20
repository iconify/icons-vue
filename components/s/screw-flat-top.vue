<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfhn1dbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfhn1dbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:screw-flat-top" /></template>
