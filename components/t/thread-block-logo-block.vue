<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kemebac4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kemebac4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:thread-block-logo-block" /></template>
