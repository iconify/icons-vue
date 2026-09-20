<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uny8lmbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uny8lmbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:snapdragon-logo-solid" /></template>
