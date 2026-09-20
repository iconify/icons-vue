<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig55-lw-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig55-lw-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mobile-signal-four-solid" /></template>
