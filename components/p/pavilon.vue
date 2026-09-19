<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hflkhep-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hflkhep-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pavilon" /></template>
