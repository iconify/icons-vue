<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7xz85ucz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7xz85ucz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:riot-games-logo-solid" /></template>
