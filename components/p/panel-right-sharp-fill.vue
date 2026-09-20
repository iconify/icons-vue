<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouaapzbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouaapzbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-sharp-fill" /></template>
