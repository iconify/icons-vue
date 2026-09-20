<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmctt_b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gmctt_b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:usb-port-flat" /></template>
