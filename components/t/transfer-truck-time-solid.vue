<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu-_jv4ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nu-_jv4ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:transfer-truck-time-solid" /></template>
