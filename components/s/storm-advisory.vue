<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em58hzb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em58hzb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:storm-advisory" /></template>
