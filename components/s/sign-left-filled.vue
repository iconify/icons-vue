<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlrq40rat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlrq40rat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sign-left-filled" /></template>
