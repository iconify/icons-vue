<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww89dpb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww89dpb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-minus" /></template>
