<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb0jkwy9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yb0jkwy9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:voice-mail-off-solid" /></template>
