<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdv9229rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kdv9229rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:usb-circle-filled" /></template>
