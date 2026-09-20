<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3gm7cbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3gm7cbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:tumblr-logo-block" /></template>
