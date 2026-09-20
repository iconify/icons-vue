<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjois9l_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rjois9l_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-sharepoint-logo-solid" /></template>
