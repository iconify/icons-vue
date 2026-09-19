<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehem8xbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehem8xbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:satoshi-v2-outline" /></template>
