<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eib1g-bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eib1g-bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:play-off" /></template>
