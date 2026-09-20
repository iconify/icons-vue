<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaogckb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaogckb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:traffic-cone" /></template>
