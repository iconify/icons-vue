<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9hj6xbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9hj6xbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-4-lock" /></template>
