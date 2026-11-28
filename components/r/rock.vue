<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmp0z4btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmp0z4btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:rock" /></template>
