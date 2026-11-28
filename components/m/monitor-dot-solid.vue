<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuzpqnbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuzpqnbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:monitor-dot-solid" /></template>
