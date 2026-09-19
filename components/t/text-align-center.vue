<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyciarxmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyciarxmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-align-center" /></template>
