<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tntdjeucf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tntdjeucf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:parcel" /></template>
