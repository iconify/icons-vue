<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2c-erjgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2c-erjgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:speedtest" /></template>
