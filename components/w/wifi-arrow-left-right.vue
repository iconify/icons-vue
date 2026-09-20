<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etss8k7ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etss8k7ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-arrow-left-right" /></template>
