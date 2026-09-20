<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvegd0fxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvegd0fxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-dot-fill" /></template>
