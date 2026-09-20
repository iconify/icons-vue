<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbk2hrbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lbk2hrbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:notification-application-1" /></template>
