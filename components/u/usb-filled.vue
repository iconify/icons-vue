<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbke41bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbke41bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:usb-filled" /></template>
