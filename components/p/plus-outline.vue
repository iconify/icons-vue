<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e48s4nboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e48s4nboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:plus-outline" /></template>
