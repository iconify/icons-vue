<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9x5xxbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9x5xxbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:qr-code" /></template>
