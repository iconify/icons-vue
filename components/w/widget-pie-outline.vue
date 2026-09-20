<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp43ed8br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp43ed8br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:widget-pie-outline" /></template>
