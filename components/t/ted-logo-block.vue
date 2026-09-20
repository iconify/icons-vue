<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0u518u-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0u518u-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:ted-logo-block" /></template>
