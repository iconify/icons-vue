<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdq0fiufx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdq0fiufx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:phone-hangup-outline" /></template>
