<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miwm2wbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miwm2wbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-paused" /></template>
