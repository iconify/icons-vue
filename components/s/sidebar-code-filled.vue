<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpzp61zkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xpzp61zkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sidebar-code-filled" /></template>
