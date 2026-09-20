<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgp5n5ugm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vgp5n5ugm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sheet-outline" /></template>
