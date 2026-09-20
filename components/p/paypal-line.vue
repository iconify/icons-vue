<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc5lombzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc5lombzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:paypal-line" /></template>
