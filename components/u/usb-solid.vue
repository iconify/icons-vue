<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmm_pxeix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmm_pxeix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:usb-solid" /></template>
