<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grvmx1blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grvmx1blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:message-alert" /></template>
