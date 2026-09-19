<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io862rkbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="io862rkbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:usb-plug-fill" /></template>
