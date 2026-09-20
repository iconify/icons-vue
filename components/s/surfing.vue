<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swj80ibqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swj80ibqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:surfing" /></template>
