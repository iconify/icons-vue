<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to7ezacez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="to7ezacez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:usbflash" /></template>
