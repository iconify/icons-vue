<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi5na0bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi5na0bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-off-line" /></template>
