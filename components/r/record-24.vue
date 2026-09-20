<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy5y0nbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy5y0nbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:record-24" /></template>
