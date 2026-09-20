<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5_zm5bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v5_zm5bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:twitter-logo-2-solid" /></template>
