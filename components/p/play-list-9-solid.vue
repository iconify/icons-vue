<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjum62tfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yjum62tfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:play-list-9-solid" /></template>
