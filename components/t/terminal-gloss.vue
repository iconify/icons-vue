<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk9e17sjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk9e17sjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:terminal-gloss" /></template>
