<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu32_sahc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu32_sahc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:roller-coaster" /></template>
