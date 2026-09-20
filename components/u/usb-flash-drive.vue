<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4er2kb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4er2kb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:usb-flash-drive" /></template>
