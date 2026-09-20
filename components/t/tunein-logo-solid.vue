<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd3hqu7km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hd3hqu7km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:tunein-logo-solid" /></template>
