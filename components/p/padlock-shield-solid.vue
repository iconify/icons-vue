<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c51yrgb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c51yrgb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:padlock-shield-solid" /></template>
