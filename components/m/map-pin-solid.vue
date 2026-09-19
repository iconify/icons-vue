<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhxc8acwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rhxc8acwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:map-pin-solid" /></template>
