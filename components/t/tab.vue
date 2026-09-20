<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tala_i6jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tala_i6jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tab" /></template>
