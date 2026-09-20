<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eruikr-ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eruikr-ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-lock" /></template>
