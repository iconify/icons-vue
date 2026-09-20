<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv9-thb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qv9-thb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shell-solid" /></template>
