<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djz7x8vob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="djz7x8vob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:usb-drive-solid" /></template>
