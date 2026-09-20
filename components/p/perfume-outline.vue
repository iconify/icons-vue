<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4-20mbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x4-20mbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:perfume-outline" /></template>
