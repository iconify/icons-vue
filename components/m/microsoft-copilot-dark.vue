<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6m1gdbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a6m1gdbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-copilot-dark" /></template>
