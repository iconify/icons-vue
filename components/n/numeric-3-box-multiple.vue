<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo5jj9iek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo5jj9iek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-3-box-multiple" /></template>
