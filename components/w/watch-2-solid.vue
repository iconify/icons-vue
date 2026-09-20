<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5vr6ibjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g5vr6ibjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:watch-2-solid" /></template>
