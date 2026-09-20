<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw1ptubmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw1ptubmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:whatsapp-logo-solid" /></template>
