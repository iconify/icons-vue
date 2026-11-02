<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxpnv3bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxpnv3bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:phone-add-line" /></template>
