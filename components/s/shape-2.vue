<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbw62cbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbw62cbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shape-2" /></template>
