<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nysmxebsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nysmxebsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:observation-outline-24px" /></template>
