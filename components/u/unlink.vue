<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv8pwk9eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv8pwk9eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:unlink" /></template>
