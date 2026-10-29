<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/max9occ2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="max9occ2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:usb-solid" /></template>
