<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwald2b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwald2b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:screwdriver-wrench" /></template>
