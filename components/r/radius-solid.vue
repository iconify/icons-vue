<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgpfcmb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wgpfcmb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:radius-solid" /></template>
