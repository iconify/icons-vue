<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q394wmbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q394wmbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:screwdriver-wrench-solid" /></template>
