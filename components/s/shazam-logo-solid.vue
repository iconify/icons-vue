<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qok2qrelu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qok2qrelu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:shazam-logo-solid" /></template>
