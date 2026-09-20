<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tged_ebbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tged_ebbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scan-2-line" /></template>
