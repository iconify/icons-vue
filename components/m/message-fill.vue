<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f--pn5glr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f--pn5glr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:message-fill" /></template>
