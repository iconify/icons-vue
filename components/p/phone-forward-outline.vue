<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmsq6ex-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmsq6ex-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-forward-outline" /></template>
