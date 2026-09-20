<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgts3ebcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fgts3ebcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pip" /></template>
