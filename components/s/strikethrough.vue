<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt73-z00d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt73-z00d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:strikethrough" /></template>
