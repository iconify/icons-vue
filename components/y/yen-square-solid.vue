<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqy3-uvcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqy3-uvcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:yen-square-solid" /></template>
