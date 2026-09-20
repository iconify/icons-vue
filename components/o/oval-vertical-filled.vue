<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds5bglbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds5bglbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:oval-vertical-filled" /></template>
