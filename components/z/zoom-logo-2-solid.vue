<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1ah6mbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1ah6mbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:zoom-logo-2-solid" /></template>
