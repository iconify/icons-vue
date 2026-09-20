<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fae5gbciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fae5gbciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:notification-bell-download-fill" /></template>
