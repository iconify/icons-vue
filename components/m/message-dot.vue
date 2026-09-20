<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6m3idbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6m3idbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-dot" /></template>
