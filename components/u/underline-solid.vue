<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqz-vvbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqz-vvbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:underline-solid" /></template>
