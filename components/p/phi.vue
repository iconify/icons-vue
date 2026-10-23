<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkpkc0b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkpkc0b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:phi" /></template>
