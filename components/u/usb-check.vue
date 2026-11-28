<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usvxjnb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usvxjnb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:usb-check" /></template>
