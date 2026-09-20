<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbox2vbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbox2vbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:passport-cancel" /></template>
