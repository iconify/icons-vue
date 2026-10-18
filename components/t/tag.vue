<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9r3v0beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9r3v0beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tag" /></template>
