<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdpam1rof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdpam1rof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shapes-2-fill" /></template>
