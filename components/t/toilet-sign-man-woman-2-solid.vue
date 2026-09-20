<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/effkhktdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="effkhktdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:toilet-sign-man-woman-2-solid" /></template>
