<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q03rfbbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q03rfbbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transform-point" /></template>
