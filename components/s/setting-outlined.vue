<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjt5249cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjt5249cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:setting-outlined" /></template>
