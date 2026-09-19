<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnfhi1qkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="cnfhi1qkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tray-gear-26" /></template>
