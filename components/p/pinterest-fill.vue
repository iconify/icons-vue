<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsgrpi4hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsgrpi4hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pinterest-fill" /></template>
