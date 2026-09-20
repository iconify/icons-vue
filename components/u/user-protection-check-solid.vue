<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h090gtm4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h090gtm4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:user-protection-check-solid" /></template>
