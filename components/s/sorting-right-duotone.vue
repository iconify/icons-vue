<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-3-4ac2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-3-4ac2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sorting-right-duotone" /></template>
