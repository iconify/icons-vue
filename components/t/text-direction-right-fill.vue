<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw6xa2_bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw6xa2_bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-direction-right-fill" /></template>
