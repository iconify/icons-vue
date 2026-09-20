<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvnh6dndp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lvnh6dndp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:usb" /></template>
