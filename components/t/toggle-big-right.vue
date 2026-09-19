<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvnle8ghx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvnle8ghx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:toggle-big-right" /></template>
