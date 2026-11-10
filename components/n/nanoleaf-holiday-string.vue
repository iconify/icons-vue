<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsd3660jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsd3660jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-holiday-string" /></template>
