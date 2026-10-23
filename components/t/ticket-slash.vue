<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2m8x4baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2m8x4baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ticket-slash" /></template>
