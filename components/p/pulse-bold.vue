<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1wo1nbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1wo1nbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pulse-bold" /></template>
