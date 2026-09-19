<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztko541ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztko541ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:power" /></template>
