<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cutibeb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cutibeb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:sketch-logo-block" /></template>
