<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtn8gnbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtn8gnbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:source-commit-local" /></template>
