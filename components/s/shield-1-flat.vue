<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/donls37ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="donls37ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:shield-1-flat" /></template>
