<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0hedib7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q0hedib7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:skip-backward-solid" /></template>
