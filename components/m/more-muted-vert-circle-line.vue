<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9s-4iwjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9s-4iwjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-muted-vert-circle-line" /></template>
