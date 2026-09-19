<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7pr4cc1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7pr4cc1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:model-x-charge" /></template>
