<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qghu-3aqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qghu-3aqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:medical-folder-solid" /></template>
