<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt144hd_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt144hd_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tray-alert" /></template>
