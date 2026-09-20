<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wci0subjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wci0subjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:stairs" /></template>
