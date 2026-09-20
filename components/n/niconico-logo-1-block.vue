<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6p_0fbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s6p_0fbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:niconico-logo-1-block" /></template>
