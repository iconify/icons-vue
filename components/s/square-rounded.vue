<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enwe_hbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enwe_hbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:square-rounded" /></template>
