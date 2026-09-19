<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upwahnbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upwahnbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:seven-z-01" /></template>
