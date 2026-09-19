<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtcb-ccwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtcb-ccwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:open-sidebar-outline" /></template>
