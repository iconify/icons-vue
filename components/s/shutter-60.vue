<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxw8ynnbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxw8ynnbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:shutter-60" /></template>
