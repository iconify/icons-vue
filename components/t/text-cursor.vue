<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6xzofb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6xzofb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:text-cursor" /></template>
