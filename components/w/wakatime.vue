<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfr8q1bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfr8q1bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:wakatime" /></template>
