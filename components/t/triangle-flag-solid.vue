<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx6yl2nkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cx6yl2nkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:triangle-flag-solid" /></template>
