<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac9dv2y0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac9dv2y0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:telegram" /></template>
