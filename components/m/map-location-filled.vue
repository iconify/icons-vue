<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw_48sfjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw_48sfjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-location-filled" /></template>
