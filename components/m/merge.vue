<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls8ogociq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls8ogociq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:merge" /></template>
