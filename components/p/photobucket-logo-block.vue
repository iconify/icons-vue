<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8n6-jbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c8n6-jbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:photobucket-logo-block" /></template>
