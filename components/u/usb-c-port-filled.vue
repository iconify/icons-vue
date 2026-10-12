<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g996dvbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g996dvbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:usb-c-port-filled" /></template>
