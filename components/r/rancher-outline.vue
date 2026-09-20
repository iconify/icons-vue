<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xii50qbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xii50qbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rancher-outline" /></template>
