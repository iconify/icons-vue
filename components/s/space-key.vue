<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jclx62bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jclx62bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:space-key" /></template>
