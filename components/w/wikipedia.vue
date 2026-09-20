<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7yhob1zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7yhob1zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wikipedia" /></template>
