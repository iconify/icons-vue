<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uagq5sbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uagq5sbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:sharing" /></template>
