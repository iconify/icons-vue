<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo0jstbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zo0jstbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-copilot-dark" /></template>
