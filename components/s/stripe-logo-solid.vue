<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikdhr5-2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikdhr5-2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:stripe-logo-solid" /></template>
