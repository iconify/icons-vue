<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qifb4r4in.css';
import '../../css/w/wtve9fz8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qifb4r4in"/><path class="wtve9fz8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:usb-c-48" /></template>
