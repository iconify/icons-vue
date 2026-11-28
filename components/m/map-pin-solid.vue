<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g527k7hvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g527k7hvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:map-pin-solid" /></template>
