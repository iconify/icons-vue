<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrox0xb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1408};
const content = `<path class="jrox0xb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:usb" /></template>
