<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm0f2cccm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lm0f2cccm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:skype-logo-2-block" /></template>
