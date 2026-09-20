<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8ap81bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8ap81bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:photography-equipment-flash-light-bold" /></template>
