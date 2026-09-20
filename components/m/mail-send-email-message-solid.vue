<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz9t_ne3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sz9t_ne3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:mail-send-email-message-solid" /></template>
