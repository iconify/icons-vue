<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7bs3sb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v7bs3sb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:volume-mute-solid" /></template>
