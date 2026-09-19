<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0fcgjs6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0fcgjs6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:message-alt" /></template>
