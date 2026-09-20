<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to1it8btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to1it8btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vertical-rotate-counterclockwise" /></template>
