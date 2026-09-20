<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvg_hlu3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvg_hlu3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-incoming-outgoing" /></template>
