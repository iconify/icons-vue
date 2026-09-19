<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6e5nze2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="y6e5nze2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tray-clipboard-26" /></template>
