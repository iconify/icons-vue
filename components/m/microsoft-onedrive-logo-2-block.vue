<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d82ny2b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d82ny2b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-onedrive-logo-2-block" /></template>
