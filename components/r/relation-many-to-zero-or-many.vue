<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zogxjvbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zogxjvbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-many-to-zero-or-many" /></template>
