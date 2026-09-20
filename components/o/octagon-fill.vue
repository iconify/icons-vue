<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqvw7_bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqvw7_bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:octagon-fill" /></template>
