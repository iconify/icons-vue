<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfinbvu-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tfinbvu-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:wip-logo-solid" /></template>
