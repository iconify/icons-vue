<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax-isfbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ax-isfbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:page-number-outline" /></template>
