<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k28hr6b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k28hr6b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:password-block-solid" /></template>
