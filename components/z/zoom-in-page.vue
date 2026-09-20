<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x33363h0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x33363h0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:zoom-in-page" /></template>
