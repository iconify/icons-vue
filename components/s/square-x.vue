<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eef02kbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eef02kbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-x" /></template>
