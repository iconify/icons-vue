<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqfv4hn_o.css';
import '../../css/w/wqp7zgnaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tqfv4hn_o"/><path class="wqp7zgnaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:view-details" /></template>
