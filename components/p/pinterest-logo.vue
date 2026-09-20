<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6fh8eb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6fh8eb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:pinterest-logo" /></template>
