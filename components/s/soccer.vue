<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1ohzv70b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1ohzv70b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:soccer" /></template>
