<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvc0-wb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvc0-wb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:usb-line" /></template>
