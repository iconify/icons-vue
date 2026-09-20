<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laxmyzbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="laxmyzbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-yammer-logo-2-block" /></template>
