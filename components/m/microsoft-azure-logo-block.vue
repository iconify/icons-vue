<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjx9i3gfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tjx9i3gfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-azure-logo-block" /></template>
