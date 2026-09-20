<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0l6w_fxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0l6w_fxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:stumble-upong-1ing-logo-block" /></template>
