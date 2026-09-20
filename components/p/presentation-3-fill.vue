<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcorcac6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcorcac6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:presentation-3-fill" /></template>
