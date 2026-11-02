<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if38d7ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if38d7ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:warning-line" /></template>
