<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miq6d5b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miq6d5b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:text-regex-asterisk" /></template>
