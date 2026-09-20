<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmu91cbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmu91cbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:tachometer-fast" /></template>
