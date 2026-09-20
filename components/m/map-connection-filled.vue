<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvmy2nbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvmy2nbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-connection-filled" /></template>
