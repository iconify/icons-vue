<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrwj86bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrwj86bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-face-fill" /></template>
