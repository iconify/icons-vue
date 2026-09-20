<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/absg48b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="absg48b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:symbol-2" /></template>
