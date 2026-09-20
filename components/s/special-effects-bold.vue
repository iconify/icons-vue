<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzjp4tb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qzjp4tb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:special-effects-bold" /></template>
