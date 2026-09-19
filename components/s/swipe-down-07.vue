<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1e3d9t9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1e3d9t9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-down-07" /></template>
