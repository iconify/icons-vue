<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq1prjqym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vq1prjqym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tall-hat-solid" /></template>
