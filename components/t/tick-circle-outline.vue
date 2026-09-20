<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ext-fqzpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ext-fqzpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:tick-circle-outline" /></template>
