<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2eom2boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e2eom2boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scanopy-dark" /></template>
