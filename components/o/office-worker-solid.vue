<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxup_rb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qxup_rb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:office-worker-solid" /></template>
