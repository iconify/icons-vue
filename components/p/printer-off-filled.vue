<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbc7vwbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gbc7vwbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:printer-off-filled" /></template>
