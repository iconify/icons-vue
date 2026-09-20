<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usmr1cmkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usmr1cmkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-messages-filled" /></template>
