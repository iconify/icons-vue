<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d20x7abpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d20x7abpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:openvpn-logo-block" /></template>
