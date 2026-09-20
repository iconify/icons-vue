<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpmn_2k3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gpmn_2k3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:telegram-logo-1-block" /></template>
