<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg16o2bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg16o2bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:screen-normal-bold" /></template>
