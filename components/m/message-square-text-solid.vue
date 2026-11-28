<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/raqhdr7fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="raqhdr7fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-text-solid" /></template>
