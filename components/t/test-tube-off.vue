<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw8fn3uor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw8fn3uor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:test-tube-off" /></template>
