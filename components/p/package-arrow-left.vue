<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv8-pwlcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv8-pwlcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-arrow-left" /></template>
