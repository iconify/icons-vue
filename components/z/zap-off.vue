<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm83-l12l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm83-l12l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:zap-off" /></template>
