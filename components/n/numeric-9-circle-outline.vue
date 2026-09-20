<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooh1spb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooh1spb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-9-circle-outline" /></template>
