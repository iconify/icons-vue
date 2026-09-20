<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le1y_9kop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le1y_9kop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:stars-c-fill" /></template>
