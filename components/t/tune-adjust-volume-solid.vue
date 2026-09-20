<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmbhatbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kmbhatbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:tune-adjust-volume-solid" /></template>
