<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh38m3ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh38m3ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:shield-light" /></template>
