<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ippaj31sh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ippaj31sh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-10-fill" /></template>
