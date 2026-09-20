<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4fbbbcls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4fbbbcls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:page-previous-outline" /></template>
