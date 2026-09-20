<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smpw6-uka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="smpw6-uka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:sina-weibo-logo-solid" /></template>
