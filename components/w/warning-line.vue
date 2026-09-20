<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyypbubrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyypbubrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:warning-line" /></template>
