<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciwaa8b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciwaa8b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:wechat-pay-logo-solid" /></template>
