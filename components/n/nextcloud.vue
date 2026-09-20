<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx7_a-boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx7_a-boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nextcloud" /></template>
