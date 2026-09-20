<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3767cc9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m3767cc9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:usb-key-16" /></template>
