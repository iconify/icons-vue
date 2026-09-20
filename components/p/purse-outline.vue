<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo2m1xbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo2m1xbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:purse-outline" /></template>
