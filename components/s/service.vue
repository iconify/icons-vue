<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eip9frb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eip9frb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:service" /></template>
