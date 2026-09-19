<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsv3bub_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsv3bub_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:shutter-80" /></template>
