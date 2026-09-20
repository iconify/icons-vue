<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkrgh5bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkrgh5bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:usb-line" /></template>
