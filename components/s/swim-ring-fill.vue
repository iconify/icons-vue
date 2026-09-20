<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uatr2mb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uatr2mb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:swim-ring-fill" /></template>
