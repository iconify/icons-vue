<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcad-6s8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcad-6s8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:usb-outline" /></template>
