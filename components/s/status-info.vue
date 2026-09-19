<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdm16pbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdm16pbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:status-info" /></template>
