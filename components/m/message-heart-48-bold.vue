<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy-u42bhp.css';
import '../../css/n/nwipklbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zy-u42bhp"/><path class="nwipklbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-heart-48-bold" /></template>
