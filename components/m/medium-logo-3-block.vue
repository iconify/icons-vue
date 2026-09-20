<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dihbw3u5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dihbw3u5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:medium-logo-3-block" /></template>
