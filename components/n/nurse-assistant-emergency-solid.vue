<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfuh-4bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vfuh-4bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:nurse-assistant-emergency-solid" /></template>
