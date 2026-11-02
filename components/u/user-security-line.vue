<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh87xdf0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh87xdf0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-security-line" /></template>
