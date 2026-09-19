<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuz0qtb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuz0qtb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plaxo" /></template>
