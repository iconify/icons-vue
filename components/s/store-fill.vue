<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziuv23_3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziuv23_3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:store-fill" /></template>
