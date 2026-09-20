<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nicmf8b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nicmf8b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-cancel" /></template>
