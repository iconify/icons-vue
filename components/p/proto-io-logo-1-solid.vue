<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opjh0-bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="opjh0-bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:proto-io-logo-1-solid" /></template>
