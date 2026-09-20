<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khq6usb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khq6usb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-west-circle-line" /></template>
