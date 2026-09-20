<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqgsxvbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqgsxvbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:temperature-centigrade" /></template>
