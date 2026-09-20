<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6f4sq5sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e6f4sq5sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rocket-chat" /></template>
