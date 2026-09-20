<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy65scbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy65scbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:satellite-uplink" /></template>
