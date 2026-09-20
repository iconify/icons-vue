<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdpn0bcda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rdpn0bcda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:tencent-weiboing-logo-block" /></template>
