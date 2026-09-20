<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dht2r7dts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dht2r7dts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ty" /></template>
