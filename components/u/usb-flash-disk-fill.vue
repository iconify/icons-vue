<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arw00qbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arw00qbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:usb-flash-disk-fill" /></template>
