<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov6vt9tgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ov6vt9tgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:usb" /></template>
