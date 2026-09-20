<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-4s82ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-4s82ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:screen-curved-bold" /></template>
