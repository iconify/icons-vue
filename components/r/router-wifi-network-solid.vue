<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to1bekb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="to1bekb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:router-wifi-network-solid" /></template>
