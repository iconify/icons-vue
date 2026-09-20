<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-i-jubqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y-i-jubqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-yammer-logo-1-solid" /></template>
