<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzab_7yls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzab_7yls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:quote-off" /></template>
