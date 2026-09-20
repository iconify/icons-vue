<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo4a1e9iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo4a1e9iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tooth-line" /></template>
