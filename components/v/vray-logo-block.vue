<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj9jdebvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qj9jdebvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:vray-logo-block" /></template>
