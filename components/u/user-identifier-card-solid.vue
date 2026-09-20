<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz29tskxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iz29tskxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-identifier-card-solid" /></template>
