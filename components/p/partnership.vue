<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wveuotbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wveuotbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:partnership" /></template>
