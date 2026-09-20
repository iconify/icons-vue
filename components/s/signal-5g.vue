<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq8e39gll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq8e39gll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:signal-5g" /></template>
