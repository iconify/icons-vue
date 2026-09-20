<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt3n99m0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rt3n99m0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:virus-antivirus-solid" /></template>
