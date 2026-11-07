<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h15mlj49b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h15mlj49b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:usb-solid" /></template>
