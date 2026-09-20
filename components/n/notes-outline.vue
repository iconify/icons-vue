<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csk3q3blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="csk3q3blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notes-outline" /></template>
