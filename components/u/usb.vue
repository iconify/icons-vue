<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eekymj8ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":24};
const content = `<path class="eekymj8ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:usb" /></template>
