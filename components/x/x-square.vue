<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfa3zybio.css';
import '../../css/s/so8u7503r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfa3zybio"/><path class="so8u7503r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:x-square" /></template>
