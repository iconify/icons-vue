<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwpl20c6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwpl20c6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:power-gloss" /></template>
