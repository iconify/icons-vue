<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqllp0bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xqllp0bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:square-enix-logo-solid" /></template>
