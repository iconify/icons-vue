<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnf772bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fnf772bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:phone-actions-bluetooth" /></template>
