<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r16s67ibb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r16s67ibb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:nintendo-network-logo-solid" /></template>
