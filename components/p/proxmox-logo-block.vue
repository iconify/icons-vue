<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1r11cbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d1r11cbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:proxmox-logo-block" /></template>
