<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhjd6lxmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhjd6lxmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:share-outline" /></template>
