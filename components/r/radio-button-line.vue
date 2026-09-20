<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtfq3bb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtfq3bb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:radio-button-line" /></template>
