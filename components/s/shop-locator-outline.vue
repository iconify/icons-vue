<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke5xwm82e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke5xwm82e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shop-locator-outline" /></template>
