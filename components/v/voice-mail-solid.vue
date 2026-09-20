<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eikux7bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eikux7bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:voice-mail-solid" /></template>
