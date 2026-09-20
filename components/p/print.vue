<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egtd8ibwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egtd8ibwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:print" /></template>
