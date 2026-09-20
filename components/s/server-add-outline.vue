<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpwy8-brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpwy8-brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:server-add-outline" /></template>
