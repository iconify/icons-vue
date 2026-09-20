<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkv3urbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkv3urbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:support-ai" /></template>
