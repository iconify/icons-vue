<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc5ykcb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kc5ykcb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-yammer-logo-2-solid" /></template>
