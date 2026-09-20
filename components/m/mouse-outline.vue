<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rep0ab8vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rep0ab8vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mouse-outline" /></template>
