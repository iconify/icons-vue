<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j14jqwbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j14jqwbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:plurk-logo-1-solid" /></template>
