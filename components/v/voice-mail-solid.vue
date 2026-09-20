<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fns2kdljk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fns2kdljk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:voice-mail-solid" /></template>
