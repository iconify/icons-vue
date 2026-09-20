<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5z5-obzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s5z5-obzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:oculus-logo-block" /></template>
