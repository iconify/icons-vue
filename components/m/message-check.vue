<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y78__mbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y78__mbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-check" /></template>
