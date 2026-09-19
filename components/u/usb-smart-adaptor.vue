<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czdoxobia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czdoxobia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:usb-smart-adaptor" /></template>
