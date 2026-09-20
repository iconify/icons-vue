<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnjt3ebxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnjt3ebxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-windows-logo-3-solid" /></template>
