<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s08sk7hat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s08sk7hat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:play" /></template>
