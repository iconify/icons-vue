<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsczfvz-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rsczfvz-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:nurse-assistant-emergency" /></template>
