<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eki-y7icr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="eki-y7icr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:voice-mail-remix" /></template>
