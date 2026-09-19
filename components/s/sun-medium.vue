<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb7iy8b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb7iy8b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sun-medium" /></template>
