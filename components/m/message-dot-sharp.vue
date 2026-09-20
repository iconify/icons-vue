<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcp0yebys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcp0yebys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-dot-sharp" /></template>
