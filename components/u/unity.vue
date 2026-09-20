<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucft0wbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucft0wbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:unity" /></template>
