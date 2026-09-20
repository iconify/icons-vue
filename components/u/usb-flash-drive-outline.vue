<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghnpihbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghnpihbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:usb-flash-drive-outline" /></template>
