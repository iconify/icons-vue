<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3wmdbiab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x3wmdbiab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rust" /></template>
