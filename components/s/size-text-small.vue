<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m60n7yb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="m60n7yb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:size-text-small" /></template>
