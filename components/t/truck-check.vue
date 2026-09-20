<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj66bgbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj66bgbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-check" /></template>
